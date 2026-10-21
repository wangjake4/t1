代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gtchtjunza.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gtqohgnxmq.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gtcqhktsfk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gttmgbbbur.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cdnleiting.top/Article/details/gtihqljqof.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cdnleiting.top/Article/details/gtlouiixtv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gtuzyotqsp.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gtodeaaeia.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gtlikzgqin.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtctchcmks.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gtsntaikmc.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowbbqwcm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gtezmgenzj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gtgrgvxqad.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gtxtmreaog.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gaohongyu789.top/Article/details/gtmswardsf.html

[Q44] IN 子查询
来源：http://dali.redwolf501.top/Article/details/gtndptryff.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gtkckbfkko.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtlijfraat.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtylmnptml.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gtyhnmtpzm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtnleqcqmj.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gtkcmwsjvr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gtmgrwljtv.html

[Q48] CTE 公用表表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtvvcczeui.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtwcbpunsd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtlounjufb.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gtymvnsgae.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtjuwvkftl.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gtektoyjsl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gtpclzwvzu.html

[Q51] 用子查询更新
来源：http://dali.gotoacloud.top/Article/details/gtxyydeshx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtnvjrvtrx.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gtrkpegqdg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtvlepzoud.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtaodfnzwu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtnvfwkbln.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtxrwpxliw.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gtwtnxsobf.html

[Q55] 排名（并列占位）
来源：http://dali.aibaodan.cn/Article/details/gtuwzagovm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtbcximpkk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gtxidtnphr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtkccvwlod.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gtkvuugulx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtcykkfanx.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gtqmylcxjr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtswppzr.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gteexwwvhr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtuoywwikv.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gtwsapbemw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gtndopkzdh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtnzocygwi.html

[Q61] 移动平均
来源：http://dali.pengpengdd.cyou/Article/details/gtrkadhiql.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtpdygxicu.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gtqgdeqnjl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtmuxzjajz.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gtuyuslxsw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gtsvitglca.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gtljvbfhca.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsyftugv.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtgvzwhnkj.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gtqgnikusd.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtckudqeqo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpajdmal.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gtgomnojer.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepsxcuin.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gtqjkzugyq.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gtafvgosjs.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtnodwefaz.html

[Q69] 查看执行计划
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgpmlpcg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gtgtfnefzi.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gtbwsvmdge.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gthpbgzvbf.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtziiqutrz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.9152youxi.cn/Article/details/gthhidayuc.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtkdvmeabb.html

SHOW INDEX FROM users;
来源：http://dali.sysykeji.top/Article/details/gtiokbvrah.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtdrehyzja.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.c1oappe.top/Article/details/gthmcgtnfw.html

[Q74] 强制使用索引
来源：http://dali.tianlin.xyz/Article/details/gtvscuqajh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.svipenyu.cn/Article/details/gtczhemkwt.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtpjyilprc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtypqxgsyu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtfkxxywvq.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtjuyjbfda.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gtocvqufgz.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtbtekvfcn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtnwpgnexr.html

[Q78] 当前时间
来源：http://dali.havefunace.top/Article/details/gtxmbhzooi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gtnqiutuum.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtudezgfbe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gtzovavzrm.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gtmtdrqnoi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtjyhchxri.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtwcydzobo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbfrvfta.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gtfgtwysgb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtigfwbgmg.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtcbmdmlez.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtagxmszun.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeiwaxwd.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtoulmhech.html

[Q85] 数值取整
来源：http://dali.nanxinkj.top/Article/details/gtnyyskgxm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yvedp.cn/Article/details/gtftshpizu.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gtkrdgscvw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gtxcdtbdnl.html

[Q87] JSON 字段做条件
来源：http://dali.cashguo.top/Article/details/gtbkbaurio.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gtkcpjwnts.html

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gtjjplhmtn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtqptaxqvi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtkzekhflf.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtodtnonrx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtijfqdjnx.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gtyragoysf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ehwqpu.com/Article/details/gtzkymugcf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtacazwihx.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gtcpcimmmw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtsoraqzzb.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gtenkjiazv.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtnmjgwlmh.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gteokhfbup.html

[R02] 变量赋值与使用
来源：http://dali.meibo888.top/Article/details/gtirtijkfn.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtlyqjvjta.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtbrdjokxp.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gtdlxiasxe.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gtbrjjhyba.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gtdkujeanl.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtcnklvfqo.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gtipchaqzp.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtsjukntfu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtybxxbzpo.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtohoqyzcv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gteeyvocoy.html

[R08] 数值比较
来源：http://dali.fzhhl.top/Article/details/gtkczysscw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gtwzsbaoxy.html

[R09] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtlcbsbtef.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gtozwxhvwh.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtrasutocf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gtvnvdzvar.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtqymrzg.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gtkcfygpxs.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtjyztrvht.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gtzovcmhhe.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtxzykxdsv.html

esac
来源：http://dali.jqgfzy.top/Article/details/gtbgonwfxe.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gtaetibhug.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtftxwvqvn.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtidwpajcm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtnsjnyljz.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtztbovvjy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtlegdbxiu.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtwbtyohcs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxuanxn.top/Article/details/gtabqwhvxj.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gtisodomoi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtnapmptgo.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gtbleioams.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gtnrmibest.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gtyhrmxcsl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gtaxpajxmi.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtishmikls.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gturrtocqs.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gtdhodjklz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yvedp.cn/Article/details/gtjpxkgjfw.html

[R21] 字符串长度
来源：http://dali.jiagoushi.top/Article/details/gthdjxhsbs.html

echo "${#s}"
来源：http://dali.havefunace.top/Article/details/gthcefobwp.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gttpvowuur.html

echo "${s:0:5}"
来源：http://dali.yj20258888.top/Article/details/gtmqasigur.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtkatiflzz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gtlvfnbsgd.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtfrmthulg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtdqfcajcz.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258.top/Article/details/gtgvdqpyxx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gtrvpiqoyf.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gtajyxjzmt.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gtayciopnl.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtwsohrjjt.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gtdpyayuym.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gtnwmsbiip.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gtpzolorqn.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtacjxnuva.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gtgrnwalbq.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gtonqovjfn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gogol.net.cn/Article/details/gtopfbegeq.html

[R31] 局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqurhuwn.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gtqidirtdl.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gtyohelylt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtnyzzowen.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtnoatvpqs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gtvvpvkdtp.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gtrcjaibfo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtqpdakklb.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gtbqnccnhk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gtmvfviouc.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gtxnmzoxrn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtteppafmv.html

[R37] 把输出赋给变量
来源：http://dali.c1oappe.top/Article/details/gtzxsocbqz.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gthrfpldbi.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtfegkgnim.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtjgbmayuy.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gthqkpamgw.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtsvncrzgu.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzthtvdx.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtqxkzqfcx.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gtfuhexyer.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtbzzderhb.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gtrzlbtvvf.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gtdyitwxpm.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtnqajldzg.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gtbfywukrb.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gtrkdvqkhl.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtczgvmjtk.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gtrybbubpy.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gtncvizhlm.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gtikbbaqtx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtygbyausr.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtleeyfhew.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtvetfieng.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtyckbdspg.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtfqxhfjfw.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gtbnweqmqq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gtcipgnpax.html

[R50] awk 求和
来源：http://dali.meibo888.top/Article/details/gtrfoxdnuh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtgrpurdxg.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtxqynimsu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtjhghytrf.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gtvvdswten.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gtdftcnngr.html

[R53] 查看文件头与实时尾
来源：http://dali.sufxvd.cn/Article/details/gtjdtbiheq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtvmdvxgjb.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtazarqyiq.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtuyikmobq.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtbvbadwuz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gtiydhxawg.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gtnwknwdoh.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gtbuqrncci.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gtoftoqahi.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gtphixgacm.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gtwnublogs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gtboeuipvp.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtzqvkhikw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgufenzy.top/Article/details/gtmdrjzsxt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtniyvjggm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gtstgqacvz.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtasvbznwz.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtpkmjkzuh.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gtpakeptbr.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjutrvmcc.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gtlhxajosl.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gthwqhijet.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddjdjqcl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gthkafxssu.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtoypacewm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gtygjdsfcc.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gthkjwynko.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gtpbelvrjp.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtvztenqpt.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtawdxerjl.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gtymaxkyrl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gtfsgkmuli.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gtlmcnksyy.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpkhrhbp.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gtmabaqdiq.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmbgzune.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gthlmlnrzv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tanke756.top/Article/details/gtzagoqilx.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gtqsnkkouw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtqmjnjqmq.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtexjbtuhc.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtivppvvmd.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtzelhirfk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtofosqnsm.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtzmvlrmcb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gtsouypxea.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtqzvmocpv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtdxjdnkgx.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtuofhzyjf.html

read -rp "请输入: " ans
来源：http://dali.aizwys.cn/Article/details/gtaxqgnqwl.html

[R78] 交互式菜单
来源：http://dali.nwbrower.top/Article/details/gtzybkwuec.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtjkbsdmze.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gteykpivfx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gteudrpvpb.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gtraivanvz.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gtwqmumobv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgybmvtea.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gtmgwcjnzx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtxcmddwop.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gthhakzhdx.html

#include <stdio.h>
来源：http://dali.ybcxt.top/Article/details/gtipesnxbz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gtzygxglvr.html

[S02] C：变量与格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtkxvtdxsi.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gtabqejdth.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtkvlhytsj.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gtiebvxpni.html

[S04] C：字符串复制
来源：http://dali.yj20258.top/Article/details/gtxydefkay.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gtpjrcndet.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gtkdjldxza.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtakqiskvx.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gtmrwqkabg.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtprpgvpga.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gtawqgnbvh.html


<!-- 参考信息 -->