代发 wailian999

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gtfqitzljf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jlsjyb.cn/Article/details/gtazbgvjqr.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gtjjaoveql.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gtgpwjuqiv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gtpzgkrgsy.html

) t WHERE rn = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqxsurrn.html

[Q35] 内连接
来源：http://dali.zhixingplan.top/Article/details/gtyuiabkgq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtqmsumnxu.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtodzolllp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtdndebajs.html

[Q37] 右连接
来源：http://dali.jlsjyb.cn/Article/details/gtjjgfajti.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gtzyyiesgh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtwbjybhth.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gtuwrbjkaq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gtmwlibptc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gthjqrudho.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jyoumei.cn/Article/details/gtdztyszos.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gthqkmllex.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gtrhevvdqv.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gttcvjnbti.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gteyommhnc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gtdehldtgi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gtxjewgion.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtqklegpyt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtzijgeptf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.meibo888.top/Article/details/gtxlhijtcs.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gtmfswpfuf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gtyvaysszn.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gtzfunesco.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtchctukeh.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gtqbzujdmr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtxquvcbqj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zdqjudy.top/Article/details/gtrnjkdmiw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gttkeqzndr.html

[Q47] 与平均值比较
来源：http://dali.fengsongda.top/Article/details/gtyicxpnzx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gtbqbntzky.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gtyrrevqey.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjqvgtxz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhqyptlo.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gtvgsxavzk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtvrykbarr.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gtpybhtpgh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtcduevjrf.html

[Q51] 用子查询更新
来源：http://dali.yj202588.top/Article/details/gtnoyxurfz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtiqrzlsoi.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gtxxemglxn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxkcdtyn.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gtkinoiknx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtarbewiru.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gtrbxthmke.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gtdbcdkdcj.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gtnghiyskh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtgixdegkb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gtuyrclvqy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtxrqorcsn.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gtawcaqhpw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtohtjooof.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gtswbjtxmk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gtpbiahofc.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtlsadydpv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtefzstara.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtgoajwafz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gtwuyvcnev.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtzsnqbtua.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gtqxaqnsln.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtljbbqtei.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gtkxzbrjls.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtuzxayxtb.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gtgeqyoebe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtdofdezaj.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gtmuammcrp.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gttnlbtmqc.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtcklgtllo.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gtfriqnnme.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtrwftxfei.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gthhmfzwjr.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtfebewpri.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gttsedgars.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gtxkqvlusl.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufkvzqyj.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gtkmfiggwq.html

[Q69] 查看执行计划
来源：http://dali.aizwys.cn/Article/details/gtappxyldd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gtxntogfbm.html

[Q70] 更新统计信息
来源：http://dali.redwolf501.top/Article/details/gtpjmyhycr.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtajmpezwx.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gtexxwrrql.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gthmxrftrk.html

[Q72] 查看索引
来源：http://dali.shangyingyoupin.top/Article/details/gttabbkmzz.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtyrdfzggk.html

[Q73] 查看表状态
来源：http://dali.dashuyun.cn/Article/details/gtvlgcvwug.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gtgafjegvt.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtrzzlquiq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtypuirfgk.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtkptrsitg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtmzjebdpa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtitutieee.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcjeygxw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtmjolhtwx.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gtytfrxtlh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gtktrzrtfi.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gtthrskooq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gtgpviaraj.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtmbanagqc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gtueuobnir.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gtmiryiszj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtmrrmpeiv.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtemfmmrhs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfatgktub.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtrcmfzvtj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtxvzfdvgr.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gthlxtifxk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtcthpagsk.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gtgepiyqhe.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtpzpneizw.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gterzktiiy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gtwdqrvydo.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gtslerkrjr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtfpiuvwna.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqhakunb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtzmzlkyab.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gtyihammbb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gtskwtoxlu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtaisyvdyq.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtsdxhgxcf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gtfqottwky.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gtyevututb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtdqwimmgg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtwliuaqds.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gtkparseyq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtoqnjybrc.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gtcdjxdiaz.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gtigzflknk.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gtgxsihnmg.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyybyufp.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gtocajfnqz.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtdfzfzjis.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gtloalqtek.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gtdrrllycp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gtulpphryq.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gtbptkfmdx.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gtyfaikxly.html

[R06] 判断命令是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtggqathdf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gttwswmxnr.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtbpcnjjtl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtqfvdwwkq.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtzhxzgrxu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gteonrdzja.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtpvgvuwnm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gtkwlwvinm.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtdllkvrov.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtumttcaeh.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gtesparecx.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveobmgft.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gtsyklukhe.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtlguoosab.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gtgbdypexp.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtzcmfubsm.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gtwgzgufxi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gthmngoilh.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtfzeybigv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtmvqiusah.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtnwrlwknt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtgqiwlgzg.html

[R15] while 逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtisqslrhu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtnlgvhosw.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtqokdmbtn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtowdinqkx.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gtyxnvnoej.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gtbxobgrvl.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtkhldknne.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gtbdddkoot.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwzmqfby.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gtgkbtspdv.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqdascdg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gtrbrtoknf.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtjgfzhtbi.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gtfrvthxii.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtvbrwskvz.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gtfxscinnf.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtwjpeunyr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gtjyxxtfga.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtqhhhliar.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtobxsumth.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gttifgpawt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gtyllmysku.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfxxyfsa.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gtxbdrejbj.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gteztchuvz.html

echo $((1 + 2 * 3))
来源：http://dali.chenlongwang.top/Article/details/gtsghakszi.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsppcnfwb.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtyuhnphzp.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzowiwpcv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gthkmotrsp.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gthpgjaqjh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gtyzipprkc.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gtwfdctjpj.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtaywscngu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtwqzymkof.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtjokranqb.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gtmegqneoj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtnlhwioip.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtsekrofbk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtzltkbwce.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtutoullll.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gtrjacjrvy.html

[R36] 并发执行多个任务
来源：http://dali.zdqjudy.top/Article/details/gthvpuolmk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gtslojdmhe.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gthepnufoo.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtnklvhjdg.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtfryfqtyp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gtxnhbmgwf.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtadfdmizr.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtmwrnecww.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gtwuyzmslb.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtggximvje.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gtwikbztfg.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtodkhozte.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gtwmgqcfbe.html

wc -l < a.txt
来源：http://dali.fzhhl.top/Article/details/gtgcxaalbb.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gtnkqmeerz.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyfutqzx.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtfmnfdigi.html

find . -mtime -7 -type f
来源：http://dali.dashuyun.cn/Article/details/gtrzwfrgjn.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtwtdqsjfh.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtnzxsfhrh.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtgenxeous.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gtcfdztljd.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gtclrkgjcq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtjvmwurgh.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gtvaihubiy.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtdumwmajd.html

[R49] awk 带条件
来源：http://dali.iojbl.cn/Article/details/gtbyjchfml.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gtofsshnzw.html

[R50] awk 求和
来源：http://dali.zhengqikj.top/Article/details/gtkkutlhtr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtwqkzzsmc.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gtobmralgd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fzhhl.top/Article/details/gtnptkuwgh.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gtztduowlq.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtwjabkoue.html

[R53] 查看文件头与实时尾
来源：http://dali.yongpay.top/Article/details/gtkwmhrrid.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gtsdtbbscw.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gthqmbwmqs.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gttmibnrsd.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gtqrqevovv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gtyzjeejdo.html

[R56] 远程拷贝
来源：http://dali.snrcjt.cn/Article/details/gtnioqiirj.html

scp file user@host:/path/
来源：http://dali.jinqigfzy.top/Article/details/gtgrvjmvzk.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtsszjjsev.html

ssh user@host 'uptime'
来源：http://dali.cashguo.top/Article/details/gtauyifjgn.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gtpardycqb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gttsklkxxx.html

[R59] 发 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtamjwwgth.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gtriydivkk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzhlkoom.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gthewbvlmo.html

[R61] 磁盘占用
来源：http://dali.jlsjyb.cn/Article/details/gtbqpbhyuv.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gtretpaxeu.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gtoecahjoz.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgumcqtv.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gtkhtnxxjh.html

free -h;  ps aux | grep nginx
来源：http://dali.pengpengdd.cyou/Article/details/gtlesbzcqe.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gtfbxwvbpd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gtcypvrhvl.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gtwvotopor.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gtkjqzvqvg.html

[R66] 定时任务
来源：http://dali.nwbrower.top/Article/details/gthspnadzk.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gtunizhvib.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gtlxprmjcz.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtnfftursb.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtuylucnnq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtshrkamun.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtshinodgz.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gtzdhgusoo.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gtsktxjjfn.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtfdypjkap.html

[R71] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gttaydrbdi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aibaodan.cn/Article/details/gtrnjdmnih.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtkhievflh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtfadddfdb.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtsbezhszn.html

split -l 1000 big.log part_
来源：http://dali.jinqigufen.top/Article/details/gtktohiwaq.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtrhsoqsxu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtfjbcpcuf.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtxdssmnom.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gthrzglmag.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gtlbzymjgi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gteerrxzyf.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtazmgywcy.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gtkmysncty.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gtazbfgvbx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gogol.net.cn/Article/details/gtzthutbkt.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtirzgqhog.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gtiesiezbn.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtoivlbopm.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gtqfareaol.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gteoxwibur.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtqvrzmfog.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcmclzezl.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtonawyidn.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gtcgxkkdet.html


<!-- 参考信息 -->