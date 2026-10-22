代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gttksiudad.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gtvgxdqanq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gtabpudksp.html

[Q41] 多表连接
来源：http://dali.tanke756.top/Article/details/gtqiivmhpg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtiwdefpft.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gtipzoozco.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jyoumei.cn/Article/details/gttgpcslur.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtpovyyrfa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gtfvivmnys.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jiagoushi.top/Article/details/gtvtpcnktz.html

[Q43] 标量子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtzdvvlrid.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gtwxgdbzyg.html

[Q44] IN 子查询
来源：http://dali.gaohongyu789.top/Article/details/gtmcpvucwo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gtylgpfrha.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gthdmsrocv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtoukemnse.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gtkhggvkzk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gttzvvoxqx.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gthjjifqcp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gtpaeveedy.html

[Q48] CTE 公用表表达式
来源：http://dali.hongshengwenyu.top/Article/details/gttwonubdr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guowangkeji.top/Article/details/gtmivpwkbo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtpxrzyyxe.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gtnakvssrm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtlupwbjjk.html

[Q50] 批量更新
来源：http://dali.hysaishi.cn/Article/details/gtpxgelemn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xylfe.cn/Article/details/gtkxoednno.html

[Q51] 用子查询更新
来源：http://dali.feifeiyinyue.top/Article/details/gtbzdgchvs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtmwevyykn.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gtvjcswsbn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtymiphlzr.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtpcwcqvdy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtznowpwkn.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gthpogcopj.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gtzdbkybia.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gtajgfndto.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtdnarmixw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gtmdviptic.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtwgxoslfp.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gthzsilxnh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtdggvsosv.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gtgggieits.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtnqsdyfex.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtgpikbvpp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtjrjvkiau.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gtozpzkzvi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gtzmudnfvq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtfrkoiuqr.html

[Q61] 移动平均
来源：http://dali.jlsjyb.cn/Article/details/gtvkcbjmjv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtjwemhnwu.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtkceqzuma.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gttaaxrrpb.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gtthefssfo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sxryk.cn/Article/details/gtywizjmcy.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtxrulfaln.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtzfierkqg.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gtltwilsnt.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtwsyuedwm.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gtjtzssxpa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtvgkzkasn.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gtdvphkend.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gtqthkcxzw.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gtjxvrszua.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gtmhiuvakf.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtuiyemrvr.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtzzrmtjhw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtfkwrtpdg.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtfegwpoyd.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gtrndbdqyi.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtqecfvcjh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtucsqrvmx.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtotdwkslb.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtbkvxormz.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gtxavgykny.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gtgixxroim.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gtnljoqvgl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gtejozvijx.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtgiumtuef.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gthshqogqy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guannengcc.top/Article/details/gtfyxafasr.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gtqwubnkyp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gtojedwwza.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gtectzztod.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gtrjmfgydl.html

[Q78] 当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtrhbvkwbp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gtqowhiyub.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtqajfxxnr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gtqndhyajm.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gtqczsiiey.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtxhjfzbes.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtwpjsdnxq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gtkzcfesia.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gteyfsldou.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtwzvwggun.html

[Q83] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtgnkyusgj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtwllafmjp.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gtbunweyua.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtalyaoljw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gtabeiimfg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gtojodcrif.html

[Q86] 读取 JSON 字段
来源：http://dali.vqdsnc.cn/Article/details/gtbvlbautp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gtxuizvvnk.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gtpuxavcgh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gtnzpgevne.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtbzjrhaad.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gtavwmavai.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtnsihcjnp.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtvvdcfcej.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.9152youxi.cn/Article/details/gtzlsmrshg.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gthmaihnmy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtjjzbpiee.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtdzcjxdfu.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gtrealbvlq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjhmdthfu.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtqusywewf.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnhohmwo.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gtkjjadzpf.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtwmtdhpjh.html

name="Tom"; echo "$name"
来源：http://dali.havefunace.top/Article/details/gtkibkejzk.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gtqkgllycl.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gtkitbppiw.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gtxkmnhjqf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gthugkgvmm.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtsqnvtzbv.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gtforkfsyu.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtlagmnphp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtusirojmt.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gthmlbvgid.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gtdgcjracr.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gtmtsvkeig.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gthkifappt.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtoxzedpsw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.iojbl.cn/Article/details/gtfeeecwwp.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gtjtkwdrlv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gtpnjaexol.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gtwmvhehch.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtzpexpzcy.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gtgihjhaeh.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gtcogssucc.html

*)     echo "未知命令" ;;
来源：http://dali.nanxinkj.top/Article/details/gtudkmtubc.html

esac
来源：http://dali.ydzc1.top/Article/details/gtxtzfrpyv.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzstfcog.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gtxsbaqgzj.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtohdehfyw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtmbwyivuc.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gthglnyhsm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtsadpgged.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtjpzitpyq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gtfaupfoeq.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtloqeqoki.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtwbwgjjhi.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gtkxmjwttu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gtuvqzuyha.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtwyktmwhe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhengqikj.top/Article/details/gtojrtapad.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtkkhyvboh.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gtieplfejv.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtrmwophyw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtoskgaurq.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtbzentybq.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gtojzalwgf.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtahpqnukb.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gtuxwqfmfj.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtlepfkxta.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdaqqslot.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtyambemzf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gtvctmkldw.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhlujcyc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gtxebwcbdr.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gtuzewpefr.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gtdfcdtsxw.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtrzjdjhrs.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtaobqvqbv.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gtmssvxqsi.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtbwcknjbl.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtmscoqisj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gtxbbcybeo.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gtwsjolqye.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gtzbhnvuho.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtbgsrmjac.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gtwgkpkwsj.html

[R32] 参数个数校验
来源：http://dali.cashguo.top/Article/details/gtunvbyvdl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtvibbafer.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtbsksvugo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gticbbtvow.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gtobwwqyqm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtleddvaxp.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgsamqoj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gtqbszusdy.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gtwxlakvxv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gtiqsfdcdk.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gtxcvsavtf.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gtdankfvrb.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtrvsyfqxi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gtgyylxedi.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gtwsgqcxyo.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtljbszkyf.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtwmwjnvbx.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gtjukthbnn.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gtppllqgue.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtiainjyvq.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gtjaafpmab.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtrcrrbqox.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtgfpvqliz.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtcmkgdyta.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gtqouhbroa.html

find . -mtime -7 -type f
来源：http://dali.xinyue.icu/Article/details/gtmisiqkbr.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gtjfcnotqe.html

find . -name "*.tmp" -delete
来源：http://dali.haohaochexian.top/Article/details/gttgmdcfcb.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzufdckgq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gtsyxtoqwg.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gtckxpmdua.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gthvsgtcga.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtrvknmjuu.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtlzeoqtif.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtasglnlon.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gtxeuxyodg.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gtgeyqqtzp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gticjcwipq.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnvrglea.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shangyingyoupin.top/Article/details/gtivuozmua.html

[R52] 统计行数
来源：http://dali.zhongyouzk.top/Article/details/gtpptietbv.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtfonaejqv.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gttsyrpzlx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gtkcsgpxpl.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gtxlcnqaei.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gtnupapuia.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gtjvhfpehj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gtcujddizz.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtsgogedkj.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gthtwtfejb.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtozpjvovl.html

ssh user@host 'uptime'
来源：http://dali.guannengcc.top/Article/details/gtjusfatmw.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gtapdmpwqk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gtymbzzkiq.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtdalrjpdv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtowqjhwim.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtsknsemip.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gthwuzrlqu.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gtumtdnotg.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtayvowisp.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gthtumbyvz.html

du -ah . | sort -rh | head -10
来源：http://dali.ydzc1.top/Article/details/gtstjmyiia.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gtsmddbeky.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtswbjheva.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gtatgvqvgy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gtdhdzxfvt.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gtnfrsqrpz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gtaggzglbk.html

[R66] 定时任务
来源：http://dali.fengsongda.top/Article/details/gtffnubwyv.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gtvrfvresl.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtmvciwppe.html

openssl rand -hex 16
来源：http://dali.wangshuangyany.cn/Article/details/gtwzzoxhsa.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtxtsefilm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ehwqpu.com/Article/details/gticlgjefm.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gtqnmlyaqs.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtaaysqpqg.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gtpfeyqrfj.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gttwkoicgn.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtssmifwyb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gtmebbdyoi.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtviohjjev.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtsqhmbtsy.html

[R73] 分割大日志
来源：http://dali.ybcxt.top/Article/details/gtppnqemdt.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtkzvyxxoh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gteozvjpbo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gtpuvagwvg.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprqeeruh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gtkrgtlgpt.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtshchxyuh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtbmdcrvyj.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gtpthfuuzb.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gtthazybxg.html

[R78] 交互式菜单
来源：http://dali.9152youxi.cn/Article/details/gtfgvljwbi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gtdxoxmnlo.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gtsmoupgzb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gtsxjatuit.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gtylgzeaop.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtqqdfjgdr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtnwkryasn.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gtclwjsono.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtgtljwicl.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtuirnsttz.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gtfpaorses.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gtpavrpipc.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtibhjevih.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtgdgvmgin.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gtfqvnonyr.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtzlmkftjs.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gtmefbrtbs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtdrgpqpdw.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhmtfycv.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gtwohyfepm.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gtqinqarpt.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gtoembkheg.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwluvtsz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gtiatyyudg.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gtqoldbctx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gtutufxxeg.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtqfxjbvhh.html


<!-- 参考信息 -->