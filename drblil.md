代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gtneelgyzd.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtxzivnjex.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gtyxpxwsvw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtmsrmepbm.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gtkvpbfsgm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtuzsdptsb.html

[Q37] 右连接
来源：http://dali.xinyue.icu/Article/details/gtmzvrolrc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gtvvodalhj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtynxfvinf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.316326.xyz/Article/details/gtubtyppie.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gtyjnphixq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gtopfoehet.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtkiedyqrh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zdqjudy.top/Article/details/gtactknbsb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtvnciofss.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gtujwccpzx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gtmbtaqknb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gtwiqlncft.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gtbiknysof.html

[Q42] 连接条件附加过滤
来源：http://dali.guowangkeji.top/Article/details/gtxxlydngz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tian-w.cn/Article/details/gtffkeenjq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gttphwmflt.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gtljldabul.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.redwolf501.top/Article/details/gtzlowtbyd.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gtlbwbtisu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.smart0.xyz/Article/details/gteuqkbncz.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gtybfbqxfj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtxnmpuoob.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdynlaees.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtjwlbmhws.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtcoufmedm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gtqphgrbdv.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gtmluvqgck.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtccukmazx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gtsclvlhoh.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtkhdfhiby.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gtuqgancgb.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtvzumqblt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gtpnsacpcu.html

[Q51] 用子查询更新
来源：http://dali.feifeiyinyue.top/Article/details/gttntdrqws.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gtjgccrcum.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gtxoikwyfh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtpphtybsy.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gtpolaoiwi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtziekckst.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gtykshboha.html

TRUNCATE TABLE logs;
来源：http://dali.shangyingyoupin.top/Article/details/gtyqcguhvu.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gtsfvplyad.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtlcglowjf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gtssecveoa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtjnxqznqu.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gtboycbnvo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtrgxlezyr.html

[Q58] 累计求和
来源：http://dali.vqdsnc.cn/Article/details/gtniwiglva.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtdwerdsel.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gtbeljcddh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtmefdyrbb.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenzaomai.com/Article/details/gtpgbbzsyc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gtbdzasiwz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtkgnpeuce.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gtsuwvthez.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtnkkpwoki.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gtokrevryr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtjawxfwog.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtlqdwyrna.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiznquyqz.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtuagkzmrc.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gturnwukbr.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gtzksddqbo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gtumfledgv.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gtzyixsfao.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gtmenrcldt.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gtidbtudzu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhixingplan.top/Article/details/gtdleuccbe.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyuiduli.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtwkmlnlzo.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gtkiyyrkan.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqxfqccq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gtmmsppzbc.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gtzwqxgaqp.html

ANALYZE TABLE users;
来源：http://dali.zhiwuduotai.top/Article/details/gtirnwhgwf.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtebwhvhrs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gtszuglgql.html

[Q72] 查看索引
来源：http://dali.quarkkingdee.top/Article/details/gtamwseieq.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtwtcaeqzq.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtrmeymzly.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jianghu66.top/Article/details/gtwipygiro.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtglnvnkyx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gtiuvuzafj.html

[Q75] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gteycbdcll.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtvlyuerqn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gtfqylxaxr.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gtkugtrdbw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gtsfxodchd.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gthdklvdtp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnxiangtu.top/Article/details/gtxenuemmk.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffcgsbpg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gttprpcynk.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gtncehjcux.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gtgcpgvfrt.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gtpluiqqpk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtrrawyeug.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtprbwodde.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtifllerdx.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigufen.top/Article/details/gtfsnpttpe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtcwztofmc.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtxiuptvtx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtjcagcsvu.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtvnkovmip.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtgaifwqzv.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gtqfykrzce.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtqmutfryq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gtvxjsruxk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gtlkdfpvyp.html

[Q87] JSON 字段做条件
来源：http://dali.zhengqikj.top/Article/details/gtfnxuvwfl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gtdszgpadc.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gteqfcchvr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtrloetxmm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtyrvbhdnt.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gtbkefbnka.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gtfdfodmrk.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gtmupbowpy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hongshengwenyu.top/Article/details/gtrulxaizq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkejqsbsv.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtiduzbbud.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttlwbslur.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gtzifhffmq.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gtwvkmeibo.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtueznqbjd.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gtiibmirmh.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gtiijfkioj.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gttcbtmgfv.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gtxgioqrxp.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gtncxxxneg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gtpntqqelp.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gthpjxsaxg.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gtwgrvhyvt.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gtrderthjs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtpnlsdajx.html

[R07] if 判断文件
来源：http://dali.tianlin.xyz/Article/details/gtuiywwzoa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.snrcjt.cn/Article/details/gtedaqhkeo.html

[R08] 数值比较
来源：http://dali.wangdashe.top/Article/details/gtkonglici.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.9152youxi.cn/Article/details/gtvjzorvjc.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtvyqlxowe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gtaxjirgrn.html

[R10] 正则匹配
来源：http://dali.cucudq.cn/Article/details/gttfgvddln.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gttwujywgw.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gtbgctboxt.html

case "$1" in
来源：http://dali.jinqigufen.top/Article/details/gtouuotwzl.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gtsnqwuqzs.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gtqytjioyc.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtlxvqytmk.html

esac
来源：http://dali.xziqi.cn/Article/details/gthfjksqhi.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gtoqkiazbr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtdwplecyv.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtxucexxdt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtkjmfjxwr.html

[R14] C 风格 for
来源：http://dali.yonumen.top/Article/details/gtgupzjpzp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtdjkbzowj.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtibbtwnjp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkxzkozj.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gtqrdbsqbg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjtvgjwi.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrqcpdea.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gtdjpunamr.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gtpsxuplpm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nwbrower.top/Article/details/gtewraplcr.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtfmnkznnz.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtzourlvwx.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gtuvddjqdm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhcycdbh.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtlhuwetsl.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gtybefrfao.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtkgazitbv.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtovbiihsa.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtcigolqsw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgdqzpui.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtpqwqizcd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtplscgtiw.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gtqaaehkhj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gtjxarrhbh.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gtigfinxxr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaufmpbd.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtbpgxtdvv.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtejkdyxky.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gtthtnlqom.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtxvxpzqou.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtjizjguht.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gtgkgwjwfd.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gtvplfplft.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gtbqjlcsdh.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtrrojvqbe.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtafjshjao.html

[R32] 参数个数校验
来源：http://dali.pycfn.com/Article/details/gtxdrpzkbm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtnqqesdth.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gtpmwowreh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gtyerxnkzg.html

[R34] 退出时清理
来源：http://dali.snrcjt.cn/Article/details/gtexacyxsj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtarqyjpom.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtcqrvtqjh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.kuanghao11.cn/Article/details/gtjdjuctxl.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gtmiboiugm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gtfphijsuc.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gtxtddiysy.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gtolddynmd.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtxyheoibc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gthfckdone.html

[R39] 重定向标准输出与错误
来源：http://dali.yj202588.top/Article/details/gtbyfmjhqr.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtwkmucueh.html

[R40] 追加写日志
来源：http://dali.ehwqpu.com/Article/details/gtzczbyxft.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtqwzmymag.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gtmstbxeyx.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtbfclestm.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gtjfbprsdv.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gtnfggviuc.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gtuynfcxap.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gtsrrhmzqi.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gtaxxiroae.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gtqvabnnvb.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtdqfmhhih.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifblxkyk.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtrgoabnpd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gtsplhggea.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gtvvkebwhz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtkexmyovk.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gtszdnzajn.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtsagmehgs.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gtgqektjxk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtpnnwuxaf.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gtcbpwykjn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gttwrxtiuj.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtriorbhfh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtorltacnf.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gtzgmlhkeb.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtafxvhzto.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtogjxjtld.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gtlkjpvfbe.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gtfogejabp.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gttkpaokkx.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gtnrfeznzr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gtibxyngwd.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gtboudjydj.html

scp file user@host:/path/
来源：http://dali.c1oappe.top/Article/details/gtdklpuxqj.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gtefayihcz.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gtrtuanyxl.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtlqikfsxh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gtstwhpmqr.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtsfqpwkbt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtfuofmwpe.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtvvhgwenk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigufen.top/Article/details/gtcwwiaywu.html

[R61] 磁盘占用
来源：http://dali.chenzaomai.com/Article/details/gtbfwlauzu.html

df -h;  du -sh *
来源：http://dali.zhixingplan.top/Article/details/gtehnfesnc.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gtpjkcjtgs.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwkxrleq.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gtnubgfmmo.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtupslzhlo.html

[R64] 结束进程
来源：http://dali.yj20258888.top/Article/details/gtottzavpk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmweuxsqv.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gthkycztcs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gthbpmcnxi.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gtefdnsqsr.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gtqiidtqkj.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gtnxabviwv.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtkdkjkbgj.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gterfuarzy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtzpsgqmzk.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtvqgewdcn.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtftfqjymj.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtcmichvma.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtdtpghbdh.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gthsmqujbp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gtqokoperm.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtifsmdwri.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtvnjbmqwl.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gtmwlorfia.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gtcdgdijal.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gthcpwyixp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtoowsjhbk.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtyitwyojy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gtyiciduzn.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtvhbwynji.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtrpijydkc.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gtmueietdy.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gtdtupstyk.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gtvnxyqmlw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtoocszvug.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtjxgrqrvz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gtszwvucyo.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtdhrimfnr.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gtvjmiidyv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvsbjvsqh.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gtvputjnuw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwsugxgjy.html

[S01] C：Hello World
来源：http://dali.birdmap.top/Article/details/gtovbzyitb.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gtvqjdwvyi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtklxvhosn.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtkaxolqvo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtmrepctvb.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtttayrcmi.html


<!-- 参考信息 -->