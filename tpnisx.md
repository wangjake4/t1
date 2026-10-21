代发 wailian999

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gthjjlnyck.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gtobhmbgzg.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gtfifpaauc.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gtgpylojpk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqyqetbl.html

) t WHERE rn = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtvscvlwlh.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gtuabxcxsy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtpxozdyfw.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gtspucyybh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtvvkeajjh.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gtcsiewyrh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gtqeiwfwaj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gtwiuejrtl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gtxxmnzrdm.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gtqudwplgi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtzwrxrotx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtazdtbxfe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sweek.top/Article/details/gtybjtfjds.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daria6918.cn/Article/details/gtpdteiudf.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gtszmpddqe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gtdbmqdjsw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtylpddhiq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gtvyiryarn.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gttufixqcw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenlongwang.top/Article/details/gtzynyuuun.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmcgrlzd.html

[Q43] 标量子查询
来源：http://dali.yangfankeji.com/Article/details/gtpfdiytgo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gtvyoluljp.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtrkoyduiq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gtivhzsdze.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gtfqrgbpsz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtoseyohdn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nwbrower.top/Article/details/gtjegujayj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobqrykky.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtqdnuyrqm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtkqmynjxg.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gtuupieytj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gtceadsoqm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gtshndafze.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gtmpzzqjav.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoswedkpx.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gtfcpeckry.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xziqi.cn/Article/details/gtaphtmdak.html

[Q51] 用子查询更新
来源：http://dali.snrcjt.cn/Article/details/gtrktwszvb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gtbxhfgznr.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gtphgkvycx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtcdujtwvn.html

[Q53] 按条件删除
来源：http://dali.chenzaomai.com/Article/details/gtnwbgncvg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.birdmap.top/Article/details/gtqxktmjiv.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gtgqgdlpzk.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gtbavyilxj.html

[Q55] 排名（并列占位）
来源：http://dali.zdqjudy.top/Article/details/gtnljwvsit.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtrciautye.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gtnylkrsyy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtxeazhcwe.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gtvjcefcnq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtrvwavucs.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gtsihvznxz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtjsidyfio.html

[Q59] 分组内累计
来源：http://dali.shuidangran.top/Article/details/gtyckeonqa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtihlotnow.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gtsjwbheos.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtyiodgamb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gtmginsfhs.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gtpalvikki.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gthzyrmesy.html

[Q62] 分组占比
来源：http://dali.redwolf501.top/Article/details/gtdmjtulyc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtelnquduw.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtgupawocn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtxalkkway.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gtkoalmmwo.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gtydsjgrfv.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gtvzkrcejt.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gtconntwxs.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtvvxqqvwx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gtzztilgsn.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gttxkdbgwb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gtkvpamsrl.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gthyyfmbgu.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtamyjshxl.html

ROLLBACK TO sp1;
来源：http://dali.redwolf501.top/Article/details/gtaxwakxqx.html

[Q69] 查看执行计划
来源：http://dali.gaohongyu789.top/Article/details/gtfjptmdop.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyudxsxnj.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gtceuvnqnk.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gtugihhwsc.html

[Q71] 查看建表语句
来源：http://dali.pycfn.com/Article/details/gtbqoelzit.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtvoxqndrk.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gtswehdrlz.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtwqksxxju.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gthnbzbjgl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gtiantvwhl.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gtlnzeijwz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtizzeqjac.html

[Q75] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtewnbgjds.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gttrlplzdg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtjfgxenoy.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gtwnjwurrj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gtubrjpriw.html

[Q77] 时间加减
来源：http://dali.wangdashe.top/Article/details/gtmpaligdl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gtdigkvqld.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtcouqdfna.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtpxbhwfza.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtnylepevi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gtdscpfldi.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gtxovndodx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtqkdjiefu.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtwkxpglwm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gtwzcswllt.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gtnxhyjqgd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtjxgdjfgp.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtaozbqygp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtglvxnbzv.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gtjuvmncvj.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtrnkmkwro.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gtywcfuysz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gtpgnfaenb.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaxdgbos.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gtkryweuxm.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gtxgvhvyam.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gtbsvrvuqw.html

[Q88] 行转列（条件聚合）
来源：http://dali.xinyue.icu/Article/details/gtfsoccboo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gtbtyxmjam.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gtkjgchmrt.html

[Q89] 判断表是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtedrgrnrs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtrexqnier.html

[Q90] 生成序号列
来源：http://dali.haohaochexian.top/Article/details/gthjvfbwlx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gtdyadikzn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtrkpbozmw.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gtcaoeljdv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtueherial.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gtjtloajyn.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtcigkuxff.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gtejjvagwp.html

[R02] 变量赋值与使用
来源：http://dali.yongpay.top/Article/details/gttyiwdjfn.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gtqkqqgaga.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtlfizmkml.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gtxwntkvzg.html

[R04] 位置参数
来源：http://dali.tian-w.cn/Article/details/gtrevyqeuq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtfcrsdeof.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gtnvblvhmk.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gtkvyuearr.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtqjarupou.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtrigxjgpt.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gthfybpaxw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtsncmneho.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gtfrtrayav.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtixoxrbyx.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtkcsgfeux.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtfwrttmml.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gtypjtqqlh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtyspyatpt.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gtcaohxucg.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqgabqrl.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtquxbeceq.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gtfayjwwrt.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gtbwtasxge.html

esac
来源：http://dali.gotoacloud.top/Article/details/gtgrpetrwa.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gtfthzfoab.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtgcxlaree.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtmbgcsmzl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtyfovtwdk.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gthueffgqo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtzeijwrtl.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtjrujychv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ivvv.top/Article/details/gtfiqzjzkq.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtysywgcpf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtepgsubnp.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gtjeuirxfz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtppcdhdxl.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gtqugjhlrj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxhxtcnx.html

[R19] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtuzmxjtqy.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gtbduydoef.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtgbiniznr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gtaqwwivcg.html

[R21] 字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsxpficv.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gtfpbdudze.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtvpugjede.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gtjeqyedmn.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtgplzoobz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gtfvkewixm.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtybiycnik.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gtfxtxbtpl.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gtxjsqrvqb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gtnkiuulig.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnretaux.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gtzwkowshw.html

[R27] 算术展开
来源：http://dali.sufxvd.cn/Article/details/gtrvtnmqxj.html

echo $((1 + 2 * 3))
来源：http://dali.zdqjudy.top/Article/details/gtebxvqeih.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gtaxvaxpic.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gthbdhjzml.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gtprifykwz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gttajvqlxq.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gtdhmrtobj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtjppuxajw.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtvdaizmuy.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gtwijxgtfg.html

[R32] 参数个数校验
来源：http://dali.shangyingyoupin.top/Article/details/gtrjwilxmm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtfnsmasxa.html

[R33] 捕获错误并提示行号
来源：http://dali.svipenyu.cn/Article/details/gtayqwljau.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gtmmhsksrl.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gtuqhgauja.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtqqrdvzez.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtlvgqpxpf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yongpay.top/Article/details/gtjdjiabrd.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gtcpsxulmx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtiujbgphl.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gtwpevmihl.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtxavbkdjp.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtkonmooxi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gtdphujnqe.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gtvgrjpstn.html

cmd > out.log 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvwewrae.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gtfmygztgj.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtpcuucndv.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gtwwyomype.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtfkvrnwxl.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtfwynikds.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gthneypczv.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gteoepbvzw.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtycfiyevq.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtsbhfcvim.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gtrfnrxbay.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gtvmdxtxqj.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gtjqoevxfn.html

[R46] 递归替换文件内容
来源：http://dali.nanxuanxn.top/Article/details/gtylbyfcjn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gtcacsjknd.html

[R47] sed 单行替换
来源：http://dali.chenzaomai.com/Article/details/gtovyqcjvf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gthavnvoyp.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gtvxwsfozi.html

awk '{print $1, $3}' a.txt
来源：http://dali.sweek.top/Article/details/gtxyoaerjz.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gtpchrqcvk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuxssjmx.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gtxdkfqvge.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gttngghplf.html

[R51] 排序去重取前几
来源：http://dali.bjfxy.top/Article/details/gtusnhfqab.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sweek.top/Article/details/gtfxjcypeo.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gticcwzxns.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtyzjlbocw.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtqqtbquto.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gtvhckjyry.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gtdczjszhn.html

diff a.txt b.txt
来源：http://dali.pycfn.com/Article/details/gtxhxzwlcn.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtqxgwhfmk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gtjutuurlh.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevavtzby.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtzqeddnsu.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gtvzqeyuue.html

ssh user@host 'uptime'
来源：http://dali.cashguo.top/Article/details/gtfcjehndt.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gtnkrtazts.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtdzwkezij.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gtomyqrlnf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cheryme.top/Article/details/gtnffkkfcl.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtksswjqdf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gtahlkgvjf.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gtwdxeekmv.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtjtdhtwlo.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gtlojwvjns.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gtkyyibryj.html

[R63] 内存与进程
来源：http://dali.meibo888.top/Article/details/gtfujzgxrf.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gtattuflmo.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvduhuxjc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gticfnbmgp.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtxnpwwhhv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gtjkmpldly.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtbzhdmier.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gtvraywsxd.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gtzvguhypt.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gtduikumzr.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbrgzsvo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gtvviwgxtr.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcslyphl.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtsstrevgp.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtdvlmqkig.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtfrfmqcfj.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtlsvteswb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gthmpwvkmx.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gtlntgeldr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtitkufslv.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtfcrprgms.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtpjkzmmzx.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gtfcohxtco.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtsydyngmk.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gtzydttrlh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gtwzbbieia.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gtqsagltvw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtbueggmmu.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtfmaarolg.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gtgcxmeqru.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtwmuuygyw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gtmlmtdmwh.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtjufywqau.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gtwqrqrrpq.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtxpnqhidz.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gtuuuxxsye.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttiuqklen.html

S. C / C++ 专题
来源：http://dali.zhongyouzk.top/Article/details/gtsqrcffok.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtybaplbpj.html

[S01] C：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtyecmpwcq.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gtihudgpot.html


<!-- 参考信息 -->