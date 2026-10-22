代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtbeegjuum.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gtghrbmcbm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtnkywnqqd.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtkoycjxff.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gtovshaaxc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gtvkyfxfte.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gtcgefyohc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtiujypsta.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gtsszyldlv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gthysejrji.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtvvdmvbvs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtdgunjjdn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gtmdwnkkdu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtsvhakhqi.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gtjutxvial.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gtiathfwnz.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gtxtqsbmdm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gtvgzwtizt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gtcpryhndc.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtdzejstoz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtlhabsqgb.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gtviwxpkry.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtgakxrnsp.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gtsevcolqi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gtrtsvvhot.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gtoprmjgrd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtfurpvxuv.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gturwckipg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gtsjnxwigt.html

[Q54] 清空表
来源：http://dali.yangfankeji.com/Article/details/gtgkwzuyvj.html

TRUNCATE TABLE logs;
来源：http://dali.xuanzx.com/Article/details/gtjoemipwy.html

[Q55] 排名（并列占位）
来源：http://dali.gzhubu.top/Article/details/gtqhvsxrey.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gtvgieludj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258888.top/Article/details/gtgnoqclrc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gthamuddmh.html

[Q57] 行号
来源：http://dali.hnxiangtu.top/Article/details/gtqpdxichp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtestpdglb.html

[Q58] 累计求和
来源：http://dali.bjfxy.top/Article/details/gtuybjobuy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjygmvmue.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gtdizylipo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmkbyypx.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtgozawmiq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gtuwxjxpad.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtxcatjytv.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gtlnrrqxzk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtqrscyjgu.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gtfjkgxyoe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtgmcikizd.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtulhtiery.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gtogloncew.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gtucdtbhfk.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gtfnbclkpd.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtjiljonch.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtuaxttiqq.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gtvblqgkpb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmdcrggv.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtuhvbyfdp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cucudq.cn/Article/details/gthjpjdgxp.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtfvhbnavu.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gtbhbmyuwj.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtoxuqvobq.html

[Q69] 查看执行计划
来源：http://dali.fengsongda.top/Article/details/gtmvxbsyhw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtgigwvjzr.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtnnznezpu.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gtkjartigh.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtavskpbod.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pengpengdd.cyou/Article/details/gtuuhcajqt.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gtslhypqgj.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtkbosgbms.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtrmqdfncp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ppjwa.cn/Article/details/gtphuwbgut.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtvqwzkiau.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gtasofibqo.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtvkbdsmdz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pycfn.com/Article/details/gtmzfvnjuu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ppjwa.cn/Article/details/gtxuiaezes.html

[Q76] 按天统计
来源：http://dali.bjfxy.top/Article/details/gtzztjzqcz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtesleegtj.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gtkifpwlif.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gtxwjjexgv.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtwsokwobn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtxrbcoztw.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gthffjqetd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dashuyun.cn/Article/details/gtjnabixlk.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuujvhtbr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtdfidphdg.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtdeuxbrmb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtjrlierog.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gtmzdcopef.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtxhbaoami.html

[Q83] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtflznunqk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtiaitwazl.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtbhwpfuvi.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtzpkhjkff.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gtmwnipmuj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcluesgkt.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gthgttdptp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gtqnonzxof.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gtnwqeumnb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuetiantiany.cn/Article/details/gtihwrsvfs.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gthydqyfmd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gtvvhbntat.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtmexpjfiw.html

[Q89] 判断表是否存在
来源：http://dali.hfpthk.cn/Article/details/gtkfalcmzf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtbkqsihty.html

[Q90] 生成序号列
来源：http://dali.zhiwuduotai.top/Article/details/gtzzgohcmo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gotoacloud.top/Article/details/gtbzvquila.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdpyeeewn.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gtrlorhoeg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthzreliwt.html

[R01] shebang 与严格模式
来源：http://dali.feifeiyinyue.top/Article/details/gtyiznzpgd.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtymlcgqkg.html

set -euo pipefail
来源：http://dali.dianchejie.cn/Article/details/gteksoewff.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gtsdqqtkxl.html

name="Tom"; echo "$name"
来源：http://dali.zhongyouzk.top/Article/details/gtjcchsvqo.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtcpbsaalf.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gtetqqjtcg.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gtvweootpn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gtuxnzzbae.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtegsraypc.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gtjxutnzmd.html

[R06] 判断命令是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtfjykcwxv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtjjsudsgl.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gtaxwmqmqb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtdteiwnzm.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtxlyalfhw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gtutnbnkvc.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtcktxssvp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gtdtqfoxni.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtcbovsfzg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtremsposu.html

[R11] case 多分支
来源：http://dali.feifeiyinyue.top/Article/details/gtiijzmjgr.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtmmmpcpuf.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtsjkawaan.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gtejaheezx.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gtjqxfggbn.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtiulocwtk.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gtqgzwnudp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gtsauxgxct.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtbuebjabb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gttfkuqnwu.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gtivuctrcm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtijyqzoti.html

[R15] while 逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtxxhnytxq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtfbjfrisi.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gtmujjnceu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtbxrxcjvk.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gtvxkjuwan.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqwfaiwh.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gtlpgwfphf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gtfusqqxii.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtlevkbxgb.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gtahpgwmtu.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gtrbeoaqqr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hywenlv.cn/Article/details/gtnrqiwppn.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtpxxucguz.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gtdxsnhsrn.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtielooyoc.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gtpyxxvnqo.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gthzdwnqpk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gtnrmnsbdf.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtogggdspf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gtpdgjnfxg.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtkypzchuj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdejwiucd.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gtjxisqndj.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gtitnevmdp.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gtzzhqayqw.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gtofwztsms.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gtwyfsmwtu.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gtjeuwkfnr.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwknldhzo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtxirrsvos.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlmqnlei.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtfmwvwqas.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gtdajytmtb.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gtnpvlpfld.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gtmecqorlo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtraapcikh.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gtyijhluev.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtbppnnedo.html

[R34] 退出时清理
来源：http://dali.snrcjt.cn/Article/details/gtgjycbchb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtcaclbgxa.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtdyzrqpxh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gtvuqbtfqy.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtltnabtvl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gtvujcvmhm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gtfvalrifn.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtirqnfxic.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gtoqagxdsc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gtxewfaarp.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtwbyiqmeu.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gtqwsnkmmc.html

[R40] 追加写日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmvgjijq.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gtuobpesio.html

[R41] 丢弃输出
来源：http://dali.gotoacloud.top/Article/details/gtflwsbyef.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gtpgurvvvf.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gtbeqdmezj.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtwmjsyzss.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gtlrzghgaa.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtglmupwzy.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gtfzqpedxt.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvxmtqnq.html

[R45] 批量删除
来源：http://dali.kuanghao11.cn/Article/details/gtnlicpweb.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbxdixhi.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gtdyrdnvxq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtddgomnls.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtcmwrbepk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gtnjsacvbj.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gtvwjstcgw.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtjkpijgja.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gtsbxararw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtechxwyoj.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gteiikotfh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtorrcatzv.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gtkynefnpk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtsehunkip.html

[R52] 统计行数
来源：http://dali.hnxiangtu.top/Article/details/gtakiqvvjy.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gthgahranf.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gtiduvjbsj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtjxoirwrj.html

[R54] 比较两个文件
来源：http://dali.jyoumei.cn/Article/details/gtcxyyumjx.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtjoddzast.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gtmrobokeg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gtiwycwywi.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gtyffgfezr.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gtxdtacrut.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gtjipummbi.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtrncxcgev.html

[R58] 下载文件
来源：http://dali.tianlin.xyz/Article/details/gtjpraysyy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtiorozjhg.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtjaxouidr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtbojrinmd.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtheekvcac.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtmlrwgsch.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gtdrestdnw.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtrvzactjn.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifxrnpkg.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gtryaitjia.html

[R63] 内存与进程
来源：http://dali.sufxvd.cn/Article/details/gtumlhueho.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqrkdyma.html

[R64] 结束进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzyxbcjl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtziufbafl.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gtztuvemef.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gtditqoyhk.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtwevgudud.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gtapofbixq.html

[R67] 生成随机十六进制串
来源：http://dali.redwolf501.top/Article/details/gtxvcqaitn.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtrdmtwknl.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtjgrlkwbe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gtwsoomgah.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gtkrjnavmh.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenzaomai.com/Article/details/gtlvbcpucf.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtcdvsmvpt.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtfbvrmkzr.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtoukndoad.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtgdvpiqao.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtfnpgemfk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtctrxhyfu.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gtbdjkqjxb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtebdwckld.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gtpamqtase.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gtddhfvczy.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtdfiyawue.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gtxcjmsmxi.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gtxevgqmun.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtpducnjss.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gtsocmebms.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gtvsbgaynd.html

[R78] 交互式菜单
来源：http://dali.yj202588.top/Article/details/gttyzkchax.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gttjifmqjv.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gtaqtkprqq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gtoqvlkddk.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtlhbkrpdz.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gtmbebfhpa.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyndjvecx.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtrsbtlymk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfsfemtcc.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtlfjxkvsz.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gtakzoftvv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtrmouyttx.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtpmpmkyxa.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gthraqvfhj.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtckfbdtwi.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gtbdeeeiqs.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtrekukoud.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtgvcpvdma.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtxjwtospy.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtjxqbtoco.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gttbrlevll.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtwxyzhavs.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gtqavsgass.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynxwgmuo.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gtofxschin.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gtbnzjmipl.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gtbieorcxp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtrfxnewai.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtxcjjgjwm.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtemjhumoz.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtsaquwuow.html


<!-- 参考信息 -->